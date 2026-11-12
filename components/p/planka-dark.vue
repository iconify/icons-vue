<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kaad2k6uy.css';
import '../../css/z/zvcyosrjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kaad2k6uy"/><path class="zvcyosrjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:planka-dark" /></template>
