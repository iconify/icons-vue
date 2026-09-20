<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypqmh3b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypqmh3b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:thumb-up-light" /></template>
