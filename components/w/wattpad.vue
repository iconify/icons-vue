<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8oo8ds2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8oo8ds2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:wattpad" /></template>
