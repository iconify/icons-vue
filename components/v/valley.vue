<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq_mdu9mg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eq_mdu9mg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:valley" /></template>
