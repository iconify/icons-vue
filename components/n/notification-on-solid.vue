<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyrkcgbkt.css';
import '../../css/p/pkjpf3lqg.css';
import '../../css/a/a-g2__2wg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyrkcgbkt"/><path clip-rule="evenodd" class="pkjpf3lqg"/><path class="a-g2__2wg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:notification-on-solid" /></template>
