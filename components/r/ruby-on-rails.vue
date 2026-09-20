<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp6xi0bom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rp6xi0bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ruby-on-rails" /></template>
