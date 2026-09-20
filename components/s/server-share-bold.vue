<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9-uq4bby.css';
import '../../css/t/txip2qdzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9-uq4bby"/><path class="txip2qdzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:server-share-bold" /></template>
