<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdwp1kh1x.css';
import '../../css/b/b3qkz99-a.css';
import '../../css/d/d1xy-t7vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xdwp1kh1x"/><path class="b3qkz99-a"/><path class="d1xy-t7vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:spot-price-20-bold" /></template>
