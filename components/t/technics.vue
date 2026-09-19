<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugl89-lzx.css';
import '../../css/a/ardjzjb-d.css';
import '../../css/p/palc4vbjx.css';
import '../../css/k/krw19nbxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugl89-lzx"/><path class="ardjzjb-d"/><path class="palc4vbjx"/><path class="krw19nbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:technics" /></template>
