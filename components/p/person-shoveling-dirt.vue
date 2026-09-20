<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzsz6cbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mzsz6cbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-shoveling-dirt" /></template>
