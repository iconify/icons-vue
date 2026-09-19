<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4plqmbyz.css';
import '../../css/z/zfukoz0sr.css';
import '../../css/t/ty52ykbzz.css';
import '../../css/v/vqhaxew3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="w4plqmbyz"/><path class="zfukoz0sr"/><circle class="ty52ykbzz"/><path class="vqhaxew3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:unlock" /></template>
