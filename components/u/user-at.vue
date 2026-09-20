<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et4jsf1wl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="et4jsf1wl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-at" /></template>
