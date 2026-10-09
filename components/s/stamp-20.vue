<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6jb10bks.css';
import '../../css/k/kp1vk88ht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q6jb10bks"/><path class="kp1vk88ht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:stamp-20" /></template>
