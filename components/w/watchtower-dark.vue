<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud2q-obza.css';
import '../../css/z/zb7vgmb5u.css';
import '../../css/u/uywxzgm7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ud2q-obza"/><path class="zb7vgmb5u"/><path class="uywxzgm7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:watchtower-dark" /></template>
