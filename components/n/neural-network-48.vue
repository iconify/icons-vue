<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmbc7curs.css';
import '../../css/f/fjd69_bck.css';
import '../../css/f/fzpp0cb-g.css';
import '../../css/a/au1zygbdq.css';
import '../../css/y/y-afifx3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hmbc7curs"/><path class="fjd69_bck"/><path class="fzpp0cb-g"/><path class="au1zygbdq"/><path class="y-afifx3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:neural-network-48" /></template>
