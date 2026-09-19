<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am18m6ban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1026};
const content = `<path class="am18m6ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:yelp" /></template>
