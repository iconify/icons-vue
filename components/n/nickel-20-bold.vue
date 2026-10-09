<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkwxxqb3q.css';
import '../../css/h/hpui6-m_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kkwxxqb3q"/><path class="hpui6-m_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:nickel-20-bold" /></template>
