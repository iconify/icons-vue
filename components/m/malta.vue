<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr8ohcc6r.css';
import '../../css/d/d2h4xtbmj.css';
import '../../css/y/y_qlxlb5x.css';
import '../../css/g/gtq3e5cts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="jr8ohcc6r"/><path class="d2h4xtbmj"/><path class="y_qlxlb5x"/><path class="gtq3e5cts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:malta" /></template>
