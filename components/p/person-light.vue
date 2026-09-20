<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_qxb9zuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_qxb9zuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:person-light" /></template>
