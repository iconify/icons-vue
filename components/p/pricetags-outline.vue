<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b91ma1vok.css';
import '../../css/v/v7d8v5b-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b91ma1vok"/><circle class="v7d8v5b-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:pricetags-outline" /></template>
