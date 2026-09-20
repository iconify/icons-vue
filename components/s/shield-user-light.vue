<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kiqehwiew.css';
import '../../css/w/we_txpblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kiqehwiew"/><path class="we_txpblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:shield-user-light" /></template>
