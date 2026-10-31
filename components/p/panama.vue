<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbr-k1iil.css';
import '../../css/l/lt6zqjfba.css';
import '../../css/e/ec33xjy3b.css';
import '../../css/v/v--6efqii.css';
import '../../css/a/azx4h1vof.css';
import '../../css/q/qdmf_5bnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="tbr-k1iil"/><path class="lt6zqjfba"/><path class="ec33xjy3b"/><path class="v--6efqii"/><path class="azx4h1vof"/><path class="qdmf_5bnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:panama" /></template>
