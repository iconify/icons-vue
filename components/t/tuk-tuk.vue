<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/e/eyjcz-sea.css';
import '../../css/u/ua1tn-b_w.css';
import '../../css/m/m9tnvhbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eyjcz-sea"/><path class="ua1tn-b_w"/><path class="m9tnvhbhu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:tuk-tuk" /></template>
