<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgsh8ibad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shield-person-outline" /></template>
<style>
.jgsh8ibad {
  fill: currentColor;
  d: path("M9.868 11.632Q9 10.764 9 9.5t.868-2.132T12 6.5t2.132.868T15 9.5t-.868 2.132T12 12.5t-2.132-.868m3.553-.71Q14 10.341 14 9.5t-.579-1.421T12 7.5t-1.421.579T10 9.5t.579 1.421T12 11.5t1.421-.579M12 20.961q-3.014-.894-5.007-3.65T5 11.1V5.692l7-2.615l7 2.615V11.1q0 3.454-1.993 6.21T12 20.963m0-16.818l-6 2.23V11.1q0 1.504.442 2.894t1.246 2.573q.973-.505 2.037-.786T12 15.5t2.275.28t2.036.787q.804-1.183 1.247-2.573Q18 12.604 18 11.1V6.375zM10.029 16.72q-.937.22-1.75.627q.763.904 1.7 1.56T12 19.9q1.085-.338 2.011-.994t1.691-1.56q-.813-.407-1.74-.627T12 16.5t-1.971.22");
}

</style>
