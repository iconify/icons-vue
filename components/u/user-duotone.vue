<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf1wx9bka.css';
import '../../css/c/czb0pkb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="pf1wx9bka"/><path clip-rule="evenodd" class="czb0pkb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:user-duotone" /></template>
