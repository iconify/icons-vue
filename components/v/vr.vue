<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kffahnbbr.css';
import '../../css/m/mozq0wb3k.css';
import '../../css/m/mgux98c7x.css';
import '../../css/n/nltiuzm9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kffahnbbr"/><path clip-rule="evenodd" class="mozq0wb3k"/><path clip-rule="evenodd" class="mgux98c7x"/><path class="nltiuzm9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:vr" /></template>
