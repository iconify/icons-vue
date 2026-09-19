<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvl2qebjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="gvl2qebjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:openshare" /></template>
