<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/f/f6vf_yxmf.css';
import '../../css/j/ja7_2f_3u.css';
import '../../css/e/ejt5gkbzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f6vf_yxmf"/><path class="ja7_2f_3u"/><path class="ejt5gkbzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:vacuum-cleaner" /></template>
