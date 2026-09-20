<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnxzfjb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cnxzfjb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorboat-on-parking-line" /></template>
