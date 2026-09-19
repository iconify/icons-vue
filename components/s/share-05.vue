<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odslhv3ql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odslhv3ql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:share-05" /></template>
