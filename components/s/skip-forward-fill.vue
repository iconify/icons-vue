<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu7embbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hu7embbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:skip-forward-fill" /></template>
