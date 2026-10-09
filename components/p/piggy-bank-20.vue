<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqqn4975g.css';
import '../../css/h/hgn5lvw7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sqqn4975g"/><path class="hgn5lvw7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:piggy-bank-20" /></template>
