<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc5dlombp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fc5dlombp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:zend" /></template>
