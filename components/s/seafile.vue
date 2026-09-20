<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exff0k9xs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exff0k9xs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:seafile" /></template>
