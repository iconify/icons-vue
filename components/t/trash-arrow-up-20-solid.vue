<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs1vf-b3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="bs1vf-b3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:trash-arrow-up-20-solid" /></template>
