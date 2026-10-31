<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn_klbhwa.css';
import '../../css/k/k18v_ab6e.css';
import '../../css/v/vfnwwubpy.css';
import '../../css/m/ms9yjsb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="jn_klbhwa"/><path class="k18v_ab6e"/><path class="vfnwwubpy"/><path class="ms9yjsb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:venezuela" /></template>
