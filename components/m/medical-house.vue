<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q254hsbwh.css';
import '../../css/q/qjavm0bgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q254hsbwh"/><path class="qjavm0bgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:medical-house" /></template>
