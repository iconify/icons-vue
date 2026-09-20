<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz0q_bwle.css';
import '../../css/o/ofqsw8bxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cz0q_bwle"/><path class="ofqsw8bxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:phone-ringing-high" /></template>
