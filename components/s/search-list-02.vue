<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj-x65o5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aj-x65o5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:search-list-02" /></template>
