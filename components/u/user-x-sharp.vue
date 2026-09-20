<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bic-v3g4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bic-v3g4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-x-sharp" /></template>
