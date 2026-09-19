<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy_kkbbcz.css';
import '../../css/b/b2wwm0bgg.css';
import '../../css/w/wv3pq4uzf.css';
import '../../css/g/gl84sdyro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qy_kkbbcz"/><path class="b2wwm0bgg"/><path class="wv3pq4uzf"/><path class="gl84sdyro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:mammogram-stacked" /></template>
