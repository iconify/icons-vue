<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5tm-zk0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="s5tm-zk0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:nfc-checkpoint" /></template>
