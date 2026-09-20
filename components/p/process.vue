<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c577txckh.css';
import '../../css/h/h8a4kwb9b.css';
import '../../css/o/okbzh_b6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c577txckh"/><path class="h8a4kwb9b"/><path class="okbzh_b6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:process" /></template>
