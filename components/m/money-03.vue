<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/a/a_9gjeb9i.css';
import '../../css/d/dzqmh_brh.css';
import '../../css/g/gi37vtblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a_9gjeb9i"/><path class="dzqmh_brh"/><path class="gi37vtblb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:money-03" /></template>
