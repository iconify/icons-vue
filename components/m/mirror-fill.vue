<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by4_c8chv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="by4_c8chv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mirror-fill" /></template>
