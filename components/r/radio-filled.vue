<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebt6dfb6z.css';
import '../../css/m/mpz6u0b-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebt6dfb6z"/><path class="mpz6u0b-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:radio-filled" /></template>
