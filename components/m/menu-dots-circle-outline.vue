<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocavnt7jz.css';
import '../../css/k/kkhl62fff.css';
import '../../css/o/o-v99zb0r.css';
import '../../css/q/q1sggqbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocavnt7jz"/><path class="kkhl62fff"/><path class="o-v99zb0r"/><path clip-rule="evenodd" class="q1sggqbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:menu-dots-circle-outline" /></template>
