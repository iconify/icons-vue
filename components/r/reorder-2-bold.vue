<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz49pjc-i.css';
import '../../css/b/bkgssdbwr.css';
import '../../css/m/mmwgdwotp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dz49pjc-i"/><path class="bkgssdbwr"/><path class="mmwgdwotp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:reorder-2-bold" /></template>
