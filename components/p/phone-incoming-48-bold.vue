<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5idgqqvy.css';
import '../../css/l/lyz0avnlk.css';
import '../../css/m/m_a345b5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b5idgqqvy"/><path class="lyz0avnlk"/><path class="m_a345b5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:phone-incoming-48-bold" /></template>
