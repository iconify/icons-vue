<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snyhutb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="snyhutb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:plus-circle-fill-20" /></template>
