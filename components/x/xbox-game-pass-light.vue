<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbch7jb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mbch7jb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:xbox-game-pass-light" /></template>
