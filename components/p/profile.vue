<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9rg-nb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h9rg-nb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:profile" /></template>
