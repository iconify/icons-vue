<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<ellipse transform="rotate(-78 23.001 8)" class="muz1v_bpf"/><path class="kz-okrb0n"/><path class="ngrb_0bjk"/><ellipse transform="rotate(-12 12.992 8)" class="hz3z20-fo"/><path class="qjrmnyb_r"/><path class="vz-qogb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:people-hugging" /></template>
<style>
.hz3z20-fo {
  cx: 12.992px;
  cy: 8px;
  fill: var(--svg-color--269, #269);
  rx: 6.75px;
  ry: 8px;
}

.kz-okrb0n {
  fill: var(--svg-color--269, #269);
  d: path("M9.724 14.687v1.579c-2.414.525-5.381 1.851-5.829 3.741C2.493 25.919 2.87 35.081 2.87 35.212v.134c0 .654.663.654 1.316.654h16.097c.653 0 1.315 0 1.315-.654V20.007c0-1.719-1.413-3.438-4.632-3.834v-1.486z");
}

.muz1v_bpf {
  cx: 23px;
  cy: 8px;
  fill: var(--svg-color--55acee, #55acee);
  rx: 8px;
  ry: 6.75px;
}

.ngrb_0bjk {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M26.276 13.303v2.963c2.414.525 5.381 1.851 5.829 3.741c1.401 5.913 1.025 15.075 1.025 15.205v.134c0 .654-.663.654-1.316.654H15.717c-.653 0-1.315 0-1.315-.654V20.007c0-1.719 1.413-3.438 4.632-3.834v-1.486z");
}

.qjrmnyb_r {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M19.092 16.088c-1.31.381-3.441.546-5.898-.382c-2.593-.98-4.978-1.944-5.908-2.268c-.846-.295-3.005-.033-3.486.848s-.753 2.485.437 3.659s7.458 3.491 9.23 4.533c.928.546.874 3.823.928 6.499c.083 4.043 7.383-13.67 4.697-12.889");
}

.vz-qogb8k {
  fill: var(--svg-color--269, #269);
  d: path("M12.233 25.283c1.331.298 3.604.811 5.999-.269c2.527-1.14 4.712-2.732 5.619-3.113c.826-.347 2.571-.683 3.532.629c.594.81.907 2.434-.207 3.679c-1.115 1.246-5.497 3.919-8.739 4.702c-2.749.664-6.967.6-8.313-.793c-2.101-2.175.281-5.245 2.109-4.835m12.758-8.048c0-1.952 1.724-3.016 3.739-3.797c.835-.324 3.005-.033 3.486.848s.753 2.485-.437 3.659s-6.788 2.294-6.788-.71");
}

</style>
