<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3fu9pp5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c3fu9pp5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:sand-watch-solid" /></template>
