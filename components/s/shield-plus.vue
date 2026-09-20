<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1hrasbfn.css';
import '../../css/k/kl1808iyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1hrasbfn"/><path class="kl1808iyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:shield-plus" /></template>
