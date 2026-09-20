<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqgkd6bzu.css';
import '../../css/s/sfxmahbnd.css';
import '../../css/q/q2-uphbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="vqgkd6bzu"/><path clip-rule="evenodd" class="sfxmahbnd"/><path class="q2-uphbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:sun-1" /></template>
