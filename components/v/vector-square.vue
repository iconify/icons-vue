<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnyw7hb_i.css';
import '../../css/o/opjoz-b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnyw7hb_i"/><path class="opjoz-b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:vector-square" /></template>
