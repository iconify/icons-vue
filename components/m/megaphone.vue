<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us_otrb6w.css';
import '../../css/o/osmzo-b7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":16};
const content = `<path class="us_otrb6w"/><path class="osmzo-b7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:megaphone" /></template>
