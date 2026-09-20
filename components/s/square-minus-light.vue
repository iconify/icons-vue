<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idssa5b9o.css';
import '../../css/r/rb33ccc5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idssa5b9o"/><path class="rb33ccc5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:square-minus-light" /></template>
