<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzsz1rwsm.css';
import '../../css/g/ggufc0siv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pzsz1rwsm"/><path class="ggufc0siv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:playlist-minimalistic-bold" /></template>
