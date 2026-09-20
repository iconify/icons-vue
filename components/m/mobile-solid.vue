<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jeqbun34w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="jeqbun34w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:mobile-solid" /></template>
