<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia3776b2n.css';
import '../../css/p/ptrhyzbub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ia3776b2n"/><path class="ptrhyzbub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sort-48" /></template>
