<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc3myab7j.css';
import '../../css/i/ixi5u0bsc.css';
import '../../css/u/ulkpqrb-s.css';
import '../../css/p/pcwgn2bgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tc3myab7j"/><path class="ixi5u0bsc"/><path class="ulkpqrb-s"/><path class="pcwgn2bgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:treehouse-20-bold" /></template>
