<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j20ot3geh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j20ot3geh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:toll" /></template>
