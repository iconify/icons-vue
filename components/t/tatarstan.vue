<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukv6olbwm.css';
import '../../css/f/fnblp6ymy.css';
import '../../css/j/jcc8b939g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="ukv6olbwm"/><path class="fnblp6ymy"/><path class="jcc8b939g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:tatarstan" /></template>
