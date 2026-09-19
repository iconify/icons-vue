<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_e7l-b5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":768};
const content = `<path class="n_e7l-b5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:mastercard" /></template>
