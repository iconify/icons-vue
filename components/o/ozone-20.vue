<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czd4skyyb.css';
import '../../css/c/cs8zgvbmz.css';
import '../../css/z/ziak3vd1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="czd4skyyb"/><path class="cs8zgvbmz"/><path class="ziak3vd1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ozone-20" /></template>
