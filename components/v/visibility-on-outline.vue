<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9d687bfw.css';
import '../../css/z/zrxq4hpuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x9d687bfw"/><path clip-rule="evenodd" class="zrxq4hpuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:visibility-on-outline" /></template>
