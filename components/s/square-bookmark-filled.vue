<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvt3gewoh.css';
import '../../css/d/doecxd77k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvt3gewoh"/><path class="doecxd77k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-bookmark-filled" /></template>
