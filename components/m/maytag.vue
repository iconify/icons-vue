<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcg-cvk0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcg-cvk0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:maytag" /></template>
