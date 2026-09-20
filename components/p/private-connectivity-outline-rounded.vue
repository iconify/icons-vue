<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyb8bibjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:private-connectivity-outline-rounded" /></template>
<style>
.lyb8bibjm {
  fill: currentColor;
  d: path("M7.916 16.413Q6.194 14.825 6.017 12.5H2.884q-.212 0-.356-.144t-.144-.357t.144-.356t.356-.143h3.133q.177-2.325 1.9-3.912Q9.638 6 12 6t4.084 1.588t1.899 3.912h3.132q.213 0 .357.144t.143.357t-.143.356t-.357.143h-3.132q-.177 2.325-1.9 3.913Q14.363 18 12 18t-4.084-1.588M12 17q2.075 0 3.538-1.463T17 12t-1.463-3.537T12 7T8.463 8.463T7 12t1.463 3.538T12 17m-2-1.73h4q.376 0 .63-.255t.254-.63v-3q0-.376-.254-.63q-.254-.255-.63-.255h-.115v-.784q0-.827-.537-1.406q-.537-.58-1.348-.58q-.787 0-1.336.554t-.549 1.331v.885H10q-.376 0-.63.254q-.254.255-.254.63v3q0 .377.254.631t.63.254m2-1.673q-.287 0-.499-.212t-.213-.5t.213-.498t.499-.213t.499.213t.213.499t-.213.499t-.499.212M10.885 10.5v-.885q0-.463.326-.789T12 8.5t.79.326t.326.79v.884zM12 12.885");
}

</style>
