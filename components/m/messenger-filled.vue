<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pybkn4b-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pybkn4b-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:messenger-filled" /></template>
