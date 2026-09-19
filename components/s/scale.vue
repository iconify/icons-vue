<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aoskosbxd.css';
import '../../css/p/puyvfbckp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aoskosbxd b"/><path class="b puyvfbckp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:scale" /></template>
