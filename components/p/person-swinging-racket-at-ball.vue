<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zoue5rbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zoue5rbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-swinging-racket-at-ball" /></template>
