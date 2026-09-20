<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0cxxdvdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="n0cxxdvdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:user-square-solid" /></template>
