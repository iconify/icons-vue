<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1gzi36pg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e1gzi36pg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-riding-skateboard" /></template>
