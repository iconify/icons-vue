<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lil6jbckh.css';
import '../../css/l/lyck5hnje.css';
import '../../css/g/g-iywcc7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lil6jbckh"/><path clip-rule="evenodd" class="lyck5hnje"/><path clip-rule="evenodd" class="g-iywcc7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:share-outline" /></template>
