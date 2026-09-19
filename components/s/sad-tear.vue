<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke7kvacnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="ke7kvacnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:sad-tear" /></template>
