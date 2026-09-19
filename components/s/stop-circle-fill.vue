<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gglhxpbss.css';
import '../../css/j/jmec2jscz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gglhxpbss"/><path class="jmec2jscz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:stop-circle-fill" /></template>
