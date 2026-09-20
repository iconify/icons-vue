<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3t6plt2w.css';
import '../../css/y/yddqsqbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n3t6plt2w"/><path clip-rule="evenodd" class="yddqsqbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:message-no-access-solid" /></template>
