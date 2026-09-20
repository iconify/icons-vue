<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_kvtnbmk.css';
import '../../css/u/u3aficb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_kvtnbmk"/><path class="u3aficb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:sign-out-fill" /></template>
