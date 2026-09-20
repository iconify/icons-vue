<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcch0_ecx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcch0_ecx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:route-sharp" /></template>
