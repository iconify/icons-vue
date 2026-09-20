<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt9x_hbmy.css';
import '../../css/s/s1wngpzxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xt9x_hbmy"/><path class="s1wngpzxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yundera-dark" /></template>
