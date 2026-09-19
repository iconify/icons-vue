<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1__e5bal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b1__e5bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:street-light" /></template>
