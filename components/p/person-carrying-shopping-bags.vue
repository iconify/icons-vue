<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dev-ydmqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dev-ydmqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-carrying-shopping-bags" /></template>
