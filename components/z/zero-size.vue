<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul95bdbte.css';
import '../../css/t/thyn37bbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ul95bdbte"/><path class="thyn37bbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:zero-size" /></template>
