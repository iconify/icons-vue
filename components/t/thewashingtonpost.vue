<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-wsdua2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-wsdua2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:thewashingtonpost" /></template>
