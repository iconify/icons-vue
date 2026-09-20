<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlz2ze66a.css';
import '../../css/n/n4hz257hz.css';
import '../../css/z/zktgoabmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vlz2ze66a"/><path clip-rule="evenodd" class="n4hz257hz"/><path class="zktgoabmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mft" /></template>
