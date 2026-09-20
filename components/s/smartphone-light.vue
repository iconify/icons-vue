<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzxq6ibab.css';
import '../../css/q/q_6cgmbmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzxq6ibab"/><path class="q_6cgmbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:smartphone-light" /></template>
