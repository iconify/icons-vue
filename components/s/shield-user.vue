<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knevdtbla.css';
import '../../css/x/xvp3v8omv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knevdtbla"/><path class="xvp3v8omv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:shield-user" /></template>
