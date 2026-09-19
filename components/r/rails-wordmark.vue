<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze3tw4bhu.css';
import '../../css/i/ikfvhgbtv.css';
import '../../css/t/tl-xxku-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ze3tw4bhu"/><path class="ikfvhgbtv"/><path class="tl-xxku-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:rails-wordmark" /></template>
