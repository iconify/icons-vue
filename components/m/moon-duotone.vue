<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kihydrb9x.css';
import '../../css/s/s1r84oshw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kihydrb9x"/><path class="s1r84oshw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:moon-duotone" /></template>
