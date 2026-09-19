<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnana9thp.css';
import '../../css/h/hpjr1hd0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnana9thp"/><path clip-rule="evenodd" class="hpjr1hd0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:skype-outline" /></template>
