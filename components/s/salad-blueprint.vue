<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/a/aov0wvjws.css';
import '../../css/r/rzbb4b4pe.css';
import '../../css/g/glwtxbcwh.css';
import '../../css/s/s7h-ahnmy.css';
import '../../css/f/f4-qlt7ko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="aov0wvjws wm-k"/><path class="rzbb4b4pe wm-a"/><ellipse class="glwtxbcwh wm-s"/><circle class="s7h-ahnmy wm-s"/><path class="f4-qlt7ko wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:salad-blueprint" /></template>
