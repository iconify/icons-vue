<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v12imcb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v12imcb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:picrew" /></template>
