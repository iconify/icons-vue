<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg0wogbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tg0wogbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:moonorbit" /></template>
