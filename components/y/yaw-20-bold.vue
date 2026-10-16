<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9orh09dv.css';
import '../../css/a/adqobuhpk.css';
import '../../css/g/g9ki1ac-n.css';
import '../../css/f/fzk7drbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b9orh09dv"/><path class="adqobuhpk"/><path class="g9ki1ac-n"/><path class="fzk7drbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:yaw-20-bold" /></template>
