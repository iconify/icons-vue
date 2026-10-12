<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-i7xbe_m.css';
import '../../css/g/g7fuoqbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-i7xbe_m"/><path clip-rule="evenodd" class="g7fuoqbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:playing-cards-filled" /></template>
