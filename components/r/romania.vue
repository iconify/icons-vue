<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwr0h7biq.css';
import '../../css/r/r_uwoyl_r.css';
import '../../css/t/t2w8mls_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="jwr0h7biq"/><path class="r_uwoyl_r"/><path class="t2w8mls_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:romania" /></template>
