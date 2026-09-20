<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsi-52frc.css';
import '../../css/k/k6b184-4c.css';
import '../../css/k/kv63i2wli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsi-52frc"/><path class="k6b184-4c"/><path class="kv63i2wli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:tablet-duotone" /></template>
