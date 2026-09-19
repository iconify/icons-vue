<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjr7h5b7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="rjr7h5b7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:sportscourt-fill" /></template>
