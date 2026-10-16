<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/siwllabzz.css';
import '../../css/n/no61rhzxq.css';
import '../../css/g/gnzoq5b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="siwllabzz"/><path class="no61rhzxq"/><path class="gnzoq5b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:spray-can-20-bold" /></template>
