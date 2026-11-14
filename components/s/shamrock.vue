<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpysmeyew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:shamrock" /></template>
<style>
.lpysmeyew {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.772 6.228q.029-1.108-1.056-2.194Q13.89 2.209 12 3.536q-1.89-1.327-3.716.498Q7.199 5.12 7.228 6.228Q6.12 6.199 5.034 7.284Q3.209 9.11 4.536 11q-1.327 1.89.498 3.716q2.071 2.07 4.224.085q.012-.01.022-.021l2.143-2.143q.688 5.109 2.967 8.299q.043.06.096.111q.054.05.117.089t.132.066q.069.026.142.038t.146.01q.074-.003.146-.019q.072-.017.139-.047q.068-.031.128-.074t.111-.096q.05-.054.089-.117t.066-.132q.026-.069.038-.142t.01-.146q-.003-.074-.019-.146q-.017-.072-.047-.139q-.031-.068-.074-.128q-1.925-2.695-2.609-7.002l1.719 1.718q.01.011.022.021q2.153 1.985 4.224-.085q1.825-1.826.498-3.716q1.327-1.89-.498-3.716q-1.086-1.085-2.194-1.056");
}

</style>
