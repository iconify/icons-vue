<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qto03pbfn.css';
import '../../css/h/hemx3sbcg.css';
import '../../css/d/dk02ivbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qto03pbfn"/><path clip-rule="evenodd" class="hemx3sbcg"/><path class="dk02ivbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:zone" /></template>
