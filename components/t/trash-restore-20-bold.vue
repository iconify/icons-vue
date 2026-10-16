<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjn6js2sa.css';
import '../../css/h/h0pvggihj.css';
import '../../css/i/i8jjk1tki.css';
import '../../css/t/t_qw8s3ib.css';
import '../../css/j/jlfhq0b_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cjn6js2sa"/><path class="h0pvggihj"/><path class="i8jjk1tki"/><path class="t_qw8s3ib"/><path class="jlfhq0b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:trash-restore-20-bold" /></template>
