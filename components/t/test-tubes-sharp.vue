<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsm1_jstp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsm1_jstp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:test-tubes-sharp" /></template>
