<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aap0qvl0c.css';
import '../../css/i/ia275-bew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aap0qvl0c"/><path class="ia275-bew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:monitor-pc-filled" /></template>
