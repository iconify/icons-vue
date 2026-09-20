<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5d2v1bhr.css';
import '../../css/w/wyn_vbbql.css';
import '../../css/p/pi1ial8rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v5d2v1bhr"/><path class="wyn_vbbql"/><path class="pi1ial8rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:tube-guyed-siren-left-siren-right" /></template>
