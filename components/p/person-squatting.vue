<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzh1ikioz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jzh1ikioz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-squatting" /></template>
