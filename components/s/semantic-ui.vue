<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsny7o2lw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsny7o2lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:semantic-ui" /></template>
