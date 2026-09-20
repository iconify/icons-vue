<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/powm5n7aj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="powm5n7aj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:play-solid" /></template>
