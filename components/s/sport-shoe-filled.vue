<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j488j5z6k.css';
import '../../css/v/vbceyt5gb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j488j5z6k"/><path class="vbceyt5gb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:sport-shoe-filled" /></template>
